<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/s/s-byc0b3i.css';
import '../../css/v/v90gbqbox.css';
import '../../css/l/l28jqobbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s-byc0b3i"/><circle class="v90gbqbox"/><path class="l28jqobbr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:image-circle-story-line" {...props}></Icon>
