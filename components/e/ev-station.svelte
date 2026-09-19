<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z74of7s3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z74of7s3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:ev-station" {...props}></Icon>
