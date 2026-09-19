<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvnjshvxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvnjshvxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:camping-filled" {...props}></Icon>
