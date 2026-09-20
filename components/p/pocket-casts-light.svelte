<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3ls1h_8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s3ls1h_8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pocket-casts-light" {...props}></Icon>
