<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4b5wgb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r4b5wgb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-yen" {...props}></Icon>
