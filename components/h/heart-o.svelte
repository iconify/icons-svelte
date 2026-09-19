<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmbg9isdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmbg9isdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:heart-o" {...props}></Icon>
