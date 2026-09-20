<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp070hbdd.css';
import '../../css/k/kdxohkplo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dp070hbdd"/><path class="kdxohkplo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:disc-solid" {...props}></Icon>
