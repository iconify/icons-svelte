<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-obboe6z.css';
import '../../css/u/u2ghli_7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k-obboe6z"/><path class="u2ghli_7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heating-boost-48" {...props}></Icon>
