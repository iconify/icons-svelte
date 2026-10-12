<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd9chqbvs.css';
import '../../css/j/jz9dkbbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sd9chqbvs"/><path class="jz9dkbbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:playlist-48" {...props}></Icon>
