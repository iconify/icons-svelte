<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/metmuqbrp.css';
import '../../css/a/aeo--wbrz.css';
import '../../css/m/mr0d03bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="metmuqbrp"/><path class="aeo--wbrz"/><path class="mr0d03bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:currency-exchange-48-bold" {...props}></Icon>
