<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2sotnbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i2sotnbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:rainy-sharp" {...props}></Icon>
