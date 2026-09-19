<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i23tf7bch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i23tf7bch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:lock" {...props}></Icon>
