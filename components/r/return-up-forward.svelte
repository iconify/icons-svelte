<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nib94r23y.css';
import '../../css/t/tp8s31b8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nib94r23y"/><path class="tp8s31b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:return-up-forward" {...props}></Icon>
