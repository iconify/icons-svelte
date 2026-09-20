<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eivc34lmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eivc34lmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:arrow-right-outline" {...props}></Icon>
