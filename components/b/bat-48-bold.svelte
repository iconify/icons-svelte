<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/biumr4bgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="biumr4bgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bat-48-bold" {...props}></Icon>
