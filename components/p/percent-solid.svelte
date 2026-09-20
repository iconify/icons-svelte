<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4zznubdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k4zznubdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:percent-solid" {...props}></Icon>
