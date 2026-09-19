<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/c/cm4ry-biv.css';
import '../../css/b/bk0qoubdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="chatbubbles-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="cm4ry-biv"/><path class="bk0qoubdl"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:chatbubbles-outline" {...props}></Icon>
