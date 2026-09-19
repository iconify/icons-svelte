<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/f/f6qf1cgpo.css';
import '../../css/h/h5zba18xq.css';
import '../../css/i/i5hlffn0h.css';
import '../../css/i/i9fzrhilo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="d2kvgvbvc"><path class="f6qf1cgpo"/><path class="h5zba18xq"/><path class="i5hlffn0h"/><path class="i9fzrhilo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:mh-1x1" {...props}></Icon>
