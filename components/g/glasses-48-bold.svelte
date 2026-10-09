<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bojscnbzb.css';
import '../../css/u/uj137zbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bojscnbzb"/><path class="uj137zbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:glasses-48-bold" {...props}></Icon>
