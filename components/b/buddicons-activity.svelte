<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6l900qvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z6l900qvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:buddicons-activity" {...props}></Icon>
