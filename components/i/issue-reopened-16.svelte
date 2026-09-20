<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsgnn88kw.css';
import '../../css/p/ph02kkyzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xsgnn88kw"/><path class="ph02kkyzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:issue-reopened-16" {...props}></Icon>
