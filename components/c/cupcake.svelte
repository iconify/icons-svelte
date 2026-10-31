<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv1d0ac5g.css';
import '../../css/h/hh5o6fbdu.css';
import '../../css/e/eeqrw937b.css';
import '../../css/a/a-avcfbzc.css';
import '../../css/n/nyieiqwii.css';
import '../../css/y/yz9mgab-j.css';
import '../../css/m/maz6fc8ol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vv1d0ac5g"/><path class="hh5o6fbdu"/><path class="eeqrw937b"/><path class="a-avcfbzc"/><path class="nyieiqwii"/><path class="yz9mgab-j"/><path class="maz6fc8ol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:cupcake" {...props}></Icon>
