<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1ftczb6h.css';
import '../../css/j/jr9qnkhrr.css';
import '../../css/a/abgd3hbgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g1ftczb6h"/><path class="jr9qnkhrr"/><path class="abgd3hbgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:price-up-48" {...props}></Icon>
