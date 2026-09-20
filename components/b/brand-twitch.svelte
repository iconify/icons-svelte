<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmoblsw2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmoblsw2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-twitch" {...props}></Icon>
