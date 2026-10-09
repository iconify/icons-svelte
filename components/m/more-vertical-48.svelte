<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq0swu20f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zq0swu20f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:more-vertical-48" {...props}></Icon>
