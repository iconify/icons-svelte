<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2u9n_9xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i2u9n_9xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:airbnb" {...props}></Icon>
