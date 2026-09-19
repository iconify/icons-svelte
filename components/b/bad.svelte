<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zko268h_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zko268h_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:bad" {...props}></Icon>
