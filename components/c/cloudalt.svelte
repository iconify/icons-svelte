<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neltabprc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="neltabprc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cloudalt" {...props}></Icon>
