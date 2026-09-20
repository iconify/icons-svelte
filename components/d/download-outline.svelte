<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml90et9yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ml90et9yu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:download-outline" {...props}></Icon>
