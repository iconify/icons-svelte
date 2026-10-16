<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq6yi9hgq.css';
import '../../css/i/icz8l1jmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vq6yi9hgq"/><path class="icz8l1jmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:notebook-pen-20" {...props}></Icon>
