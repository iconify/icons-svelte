<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v97a6o29o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v97a6o29o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:laravel" {...props}></Icon>
