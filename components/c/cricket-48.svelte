<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezw6blbcm.css';
import '../../css/p/pwe_-ab6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ezw6blbcm"/><path class="pwe_-ab6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cricket-48" {...props}></Icon>
