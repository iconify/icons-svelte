<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e49if73uf.css';
import '../../css/e/emcb5offr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e49if73uf"/><path class="emcb5offr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ethernet-port-20-bold" {...props}></Icon>
