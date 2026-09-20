<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9--2esxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h9--2esxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:radial-rays-20-solid" {...props}></Icon>
