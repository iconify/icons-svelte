<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghd2p1bfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghd2p1bfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:coding-apps-website-big-data-database-globality-velocity-bold" {...props}></Icon>
