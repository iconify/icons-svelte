<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxjuepbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxjuepbzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:angle-double-left" {...props}></Icon>
