<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iio2e3udq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iio2e3udq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gasoline-pump-with-exclamation-point" {...props}></Icon>
