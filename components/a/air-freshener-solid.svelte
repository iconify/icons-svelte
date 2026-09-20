<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s74x4zxov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s74x4zxov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:air-freshener-solid" {...props}></Icon>
