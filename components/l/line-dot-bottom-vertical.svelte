<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziw0cxgdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ziw0cxgdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:line-dot-bottom-vertical" {...props}></Icon>
