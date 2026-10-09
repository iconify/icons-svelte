<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkwo4-r4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kkwo4-r4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:loader-2-48" {...props}></Icon>
