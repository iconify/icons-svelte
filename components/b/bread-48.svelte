<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw_wrbbbz.css';
import '../../css/f/ftl4kn5-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kw_wrbbbz"/><path class="ftl4kn5-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bread-48" {...props}></Icon>
