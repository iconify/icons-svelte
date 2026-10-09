<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhfbtcy6k.css';
import '../../css/c/cf6_evf1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bhfbtcy6k"/><path class="cf6_evf1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:deforestation-48-bold" {...props}></Icon>
