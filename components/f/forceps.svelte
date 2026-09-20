<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fizl9pbgx.css';
import '../../css/n/nq7w58mhy.css';
import '../../css/k/kh_i8p3mc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="fizl9pbgx"/><path class="nq7w58mhy"/><path class="kh_i8p3mc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:forceps" {...props}></Icon>
