<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkn_koeov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dkn_koeov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:aiassistant-wordmark" {...props}></Icon>
