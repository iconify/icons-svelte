<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssjb5oo1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ssjb5oo1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:border-top" {...props}></Icon>
