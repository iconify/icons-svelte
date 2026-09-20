<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/b/bxu-zvbux.css';
import '../../css/l/ly8wnrbrd.css';
import '../../css/h/ha152abug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bxu-zvbux"/><path class="ly8wnrbrd"/><path class="ha152abug"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:ribbon" {...props}></Icon>
