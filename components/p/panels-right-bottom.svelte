<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yueg-wzbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yueg-wzbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panels-right-bottom" {...props}></Icon>
