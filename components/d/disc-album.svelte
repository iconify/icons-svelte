<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/q/q1m15dbht.css';
import '../../css/o/o3t_kjb7a.css';
import '../../css/y/y7zppqbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="q1m15dbht"/><path class="o3t_kjb7a"/><path class="y7zppqbne"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:disc-album" {...props}></Icon>
