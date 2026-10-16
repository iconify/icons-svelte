<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b20gz5bfs.css';
import '../../css/b/bv0gny4-m.css';
import '../../css/o/on0pidpto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b20gz5bfs"/><path class="bv0gny4-m"/><path class="on0pidpto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipe-wrench-20" {...props}></Icon>
