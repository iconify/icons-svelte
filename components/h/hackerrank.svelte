<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uts5pebbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uts5pebbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hackerrank" {...props}></Icon>
