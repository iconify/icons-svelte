<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1uu6_bco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m1uu6_bco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:printer" {...props}></Icon>
