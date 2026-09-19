<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6xt5c87v.css';
import '../../css/n/n_fmt7b_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="j6xt5c87v"/><path class="n_fmt7b_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:football-outline" {...props}></Icon>
