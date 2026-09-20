<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlxixtbzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlxixtbzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-fortnite" {...props}></Icon>
