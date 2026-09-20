<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj0oiablv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dj0oiablv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bath-outline" {...props}></Icon>
