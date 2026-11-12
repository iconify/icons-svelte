<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvhcjuz2f.css';
import '../../css/y/ydehlhbbh.css';
import '../../css/c/ck0nwgb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hvhcjuz2f"/><path class="ydehlhbbh"/><path class="ck0nwgb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nanoclaw-light" {...props}></Icon>
