<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arebbvaap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1408};
const content = `<g transform="translate(1792 0) scale(-1 1)"><path class="arebbvaap"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:align-right" {...props}></Icon>
