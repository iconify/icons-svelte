<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/t/t5h_azk5i.css';
import '../../css/j/jnd-e9m6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="t5h_azk5i"/><path class="jnd-e9m6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:ai-platform" {...props}></Icon>
