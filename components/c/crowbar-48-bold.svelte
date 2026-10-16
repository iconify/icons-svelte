<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxoeczbkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hxoeczbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crowbar-48-bold" {...props}></Icon>
