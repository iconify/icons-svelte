<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_7fyptgq.css';
import '../../css/v/v-wpb5q2n.css';
import '../../css/m/ms3vv49wg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z_7fyptgq"/><path class="v-wpb5q2n"/><path class="ms3vv49wg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bookmark-plus-20" {...props}></Icon>
