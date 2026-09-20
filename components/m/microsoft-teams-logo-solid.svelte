<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gugnveb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gugnveb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:microsoft-teams-logo-solid" {...props}></Icon>
