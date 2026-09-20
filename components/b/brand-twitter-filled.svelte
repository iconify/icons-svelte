<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa9yf7bhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa9yf7bhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-twitter-filled" {...props}></Icon>
