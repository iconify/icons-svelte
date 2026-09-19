<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/h/hxl5el8-f.css';
import '../../css/t/thgdu0bta.css';
import '../../css/d/d62ydupxb.css';
import '../../css/g/gop114bue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><circle class="hxl5el8-f"/><circle class="thgdu0bta"/><circle class="d62ydupxb"/><path class="gop114bue"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:git-merge" {...props}></Icon>
