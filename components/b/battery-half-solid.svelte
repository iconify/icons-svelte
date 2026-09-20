<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2qaxgb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x2qaxgb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:battery-half-solid" {...props}></Icon>
