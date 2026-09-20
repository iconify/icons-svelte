<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqvpc5b1j.css';
import '../../css/o/osrarucge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dqvpc5b1j"/><path class="osrarucge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:bookmark-list-rtl" {...props}></Icon>
