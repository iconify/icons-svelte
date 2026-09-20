<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/i/ivf7b8b3g.css';
import '../../css/h/h_tsn8bxt.css';
import '../../css/o/okp7pp4nk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ivf7b8b3g"/><circle class="h_tsn8bxt"/><path class="okp7pp4nk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:money-minus-line" {...props}></Icon>
