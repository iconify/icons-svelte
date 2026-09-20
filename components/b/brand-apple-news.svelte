<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs1d1eb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qs1d1eb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-apple-news" {...props}></Icon>
