<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5eud-qii.css';
import '../../css/o/o3vojhb_l.css';
import '../../css/l/lkn0kjb2g.css';
import '../../css/w/w1bzx4bce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a5eud-qii"/><path class="o3vojhb_l"/><path class="lkn0kjb2g"/><path class="w1bzx4bce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:bean" {...props}></Icon>
