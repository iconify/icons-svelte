<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmexqgbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmexqgbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:coding-apps-website-network-globe-bold" {...props}></Icon>
