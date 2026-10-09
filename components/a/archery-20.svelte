<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndv3dvc2g.css';
import '../../css/f/fi80utbym.css';
import '../../css/q/qyvlp9bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ndv3dvc2g"/><path class="fi80utbym"/><path class="qyvlp9bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:archery-20" {...props}></Icon>
