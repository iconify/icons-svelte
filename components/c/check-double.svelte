<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnbsg9ofn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnbsg9ofn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:check-double" {...props}></Icon>
