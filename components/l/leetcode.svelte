<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvlx87bnz.css';
import '../../css/e/eud0165so.css';
import '../../css/b/bpxdh911r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xvlx87bnz"/><path class="eud0165so"/><path class="bpxdh911r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:leetcode" {...props}></Icon>
