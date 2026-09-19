<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u87poccup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u87poccup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pen-connect-bluetooth" {...props}></Icon>
