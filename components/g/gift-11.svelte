<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml_lf0bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="ml_lf0bzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:gift-11" {...props}></Icon>
