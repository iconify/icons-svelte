<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brqvmbc5r.css';
import '../../css/f/fbs_2vnbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="brqvmbc5r"/><path class="fbs_2vnbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coins-20" {...props}></Icon>
