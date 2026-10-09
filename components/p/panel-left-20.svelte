<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofts-6g4o.css';
import '../../css/c/cqvp3bvcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ofts-6g4o"/><path class="cqvp3bvcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:panel-left-20" {...props}></Icon>
