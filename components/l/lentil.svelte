<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwdk8rb8z.css';
import '../../css/g/g32g6sb1v.css';
import '../../css/w/w5iegtdxh.css';
import '../../css/o/or1tl4bac.css';
import '../../css/j/j2po2xbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cwdk8rb8z"/><path class="g32g6sb1v"/><path class="w5iegtdxh"/><path class="or1tl4bac"/><path class="j2po2xbbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:lentil" {...props}></Icon>
