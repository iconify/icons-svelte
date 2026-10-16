<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igky23bwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="igky23bwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hot-rock-48-bold" {...props}></Icon>
