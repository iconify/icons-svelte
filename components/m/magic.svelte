<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx-l_4b3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dx-l_4b3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:magic" {...props}></Icon>
