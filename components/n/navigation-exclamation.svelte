<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v75zvrbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v75zvrbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:navigation-exclamation" {...props}></Icon>
