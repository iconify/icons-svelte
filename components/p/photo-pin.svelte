<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/k/k50zonbqn.css';
import '../../css/j/j--gz1axz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k50zonbqn"/><path class="j--gz1axz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:photo-pin" {...props}></Icon>
