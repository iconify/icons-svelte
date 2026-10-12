<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a88-_pnxg.css';
import '../../css/o/ocasejnlo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a88-_pnxg"/><path class="ocasejnlo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:discount-48-bold" {...props}></Icon>
