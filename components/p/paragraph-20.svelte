<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_54f839h.css';
import '../../css/n/nrm4cfbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j_54f839h"/><path class="nrm4cfbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paragraph-20" {...props}></Icon>
