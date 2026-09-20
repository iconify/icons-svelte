<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgo2dqivu.css';
import '../../css/s/s4p2w4bkv.css';
import '../../css/r/rxz6rmbtd.css';
import '../../css/w/w181xqb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tgo2dqivu"/><path class="s4p2w4bkv"/><path class="rxz6rmbtd"/><path class="w181xqb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:react-ts" {...props}></Icon>
