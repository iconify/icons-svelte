<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiq5bukpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kiq5bukpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:dashboard-round" {...props}></Icon>
