<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf6id7bqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tf6id7bqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gold-bar-48-bold" {...props}></Icon>
