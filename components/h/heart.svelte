<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1u70wbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1u70wbri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:heart" {...props}></Icon>
