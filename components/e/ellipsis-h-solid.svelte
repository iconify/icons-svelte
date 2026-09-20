<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4abl3zcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4abl3zcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:ellipsis-h-solid" {...props}></Icon>
