<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/u/u9gt4zbtb.css';
import '../../css/l/lohg7zkdn.css';
import '../../css/n/nol19vq4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u9gt4zbtb"/><path class="lohg7zkdn"/><circle class="nol19vq4t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:image-play" {...props}></Icon>
