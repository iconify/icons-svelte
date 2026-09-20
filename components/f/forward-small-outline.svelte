<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp4s3mbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yp4s3mbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:forward-small-outline" {...props}></Icon>
