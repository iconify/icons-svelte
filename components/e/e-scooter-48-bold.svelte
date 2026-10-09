<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3wg84b-p.css';
import '../../css/i/ikxx9ebbh.css';
import '../../css/z/zm9x9jbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o3wg84b-p"/><path class="ikxx9ebbh"/><path class="zm9x9jbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:e-scooter-48-bold" {...props}></Icon>
