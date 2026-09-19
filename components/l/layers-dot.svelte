<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjj249buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xjj249buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:layers-dot" {...props}></Icon>
