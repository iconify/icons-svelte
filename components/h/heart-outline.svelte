<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf1jg77_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lf1jg77_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:heart-outline" {...props}></Icon>
