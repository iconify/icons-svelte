<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwps5fmjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bwps5fmjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:page-down-solid" {...props}></Icon>
