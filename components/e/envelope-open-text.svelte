<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdl45rbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mdl45rbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:envelope-open-text" {...props}></Icon>
