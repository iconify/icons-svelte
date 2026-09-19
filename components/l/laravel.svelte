<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by-oj7bvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="by-oj7bvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:laravel" {...props}></Icon>
