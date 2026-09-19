<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkl44nb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kkl44nb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:currency-yen" {...props}></Icon>
