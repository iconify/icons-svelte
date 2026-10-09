<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4enznbyj.css';
import '../../css/k/kjieaf7cx.css';
import '../../css/p/pvg5xqbkw.css';
import '../../css/y/y99owegkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x4enznbyj"/><path class="kjieaf7cx"/><path class="pvg5xqbkw"/><path class="y99owegkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:multimeter-20-bold" {...props}></Icon>
