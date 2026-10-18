<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm0xcdcgi.css';
import '../../css/b/b2xtvx_in.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mm0xcdcgi"/><path class="b2xtvx_in"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:biochar-20-bold" {...props}></Icon>
