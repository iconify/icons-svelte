<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-d78hkpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-d78hkpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-h-fill-round" {...props}></Icon>
