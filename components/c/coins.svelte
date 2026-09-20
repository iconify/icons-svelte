<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/rq-dtviiy.css';
import '../../css/u/ua1ar1baw.css';
import '../../css/t/t3294rb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rq-dtviiy"/><path class="ua1ar1baw"/><circle class="t3294rb2m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:coins" {...props}></Icon>
