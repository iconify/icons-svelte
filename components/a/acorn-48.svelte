<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvn4mfbec.css';
import '../../css/l/lahmkil_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gvn4mfbec"/><path class="lahmkil_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:acorn-48" {...props}></Icon>
