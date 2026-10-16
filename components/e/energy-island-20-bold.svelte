<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdh5c-m9v.css';
import '../../css/b/bf8izsb7o.css';
import '../../css/q/qdhnwmbfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jdh5c-m9v"/><path class="bf8izsb7o"/><path class="qdhnwmbfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-island-20-bold" {...props}></Icon>
