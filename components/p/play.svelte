<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6b7xs03c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6b7xs03c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:play" {...props}></Icon>
