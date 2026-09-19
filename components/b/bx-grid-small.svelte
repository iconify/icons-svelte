<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfs4r6bkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfs4r6bkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-grid-small" {...props}></Icon>
