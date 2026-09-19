<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emp192bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="emp192bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:facebook-f" {...props}></Icon>
