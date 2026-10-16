<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiabuuwes.css';
import '../../css/h/hpxwjdbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fiabuuwes"/><path class="hpxwjdbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:data-pipeline-20" {...props}></Icon>
