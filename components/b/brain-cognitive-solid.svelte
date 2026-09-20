<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgyv-onwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mgyv-onwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:brain-cognitive-solid" {...props}></Icon>
