<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p72eivapz.css';
import '../../css/t/tbo-rh1-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p72eivapz"/><path class="tbo-rh1-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chainsaw-48-bold" {...props}></Icon>
