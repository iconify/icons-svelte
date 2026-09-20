<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgej7mwsz.css';
import '../../css/y/ysf6s1bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgej7mwsz"/><path class="ysf6s1bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-search-fill" {...props}></Icon>
