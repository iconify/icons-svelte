<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3kwf5bnk.css';
import '../../css/o/osinw2bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u3kwf5bnk"/><path class="osinw2bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pyramid-48" {...props}></Icon>
