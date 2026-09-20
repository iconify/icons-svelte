<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly42ygbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ly42ygbuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:moon" {...props}></Icon>
