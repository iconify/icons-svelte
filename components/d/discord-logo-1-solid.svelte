<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4ffnb20s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k4ffnb20s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:discord-logo-1-solid" {...props}></Icon>
