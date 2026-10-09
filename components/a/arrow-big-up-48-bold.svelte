<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdag1bnag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cdag1bnag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-big-up-48-bold" {...props}></Icon>
