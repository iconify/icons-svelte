<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iiu_lpbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iiu_lpbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:house-outline" {...props}></Icon>
