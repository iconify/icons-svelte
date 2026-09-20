<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-g-0cb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="q-g-0cb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:archlinux" {...props}></Icon>
