<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6_diewni.css';
import '../../css/y/yjg9io82y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c6_diewni"/><path class="yjg9io82y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pencil-48-bold" {...props}></Icon>
