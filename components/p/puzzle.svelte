<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eep2siwjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eep2siwjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:puzzle" {...props}></Icon>
