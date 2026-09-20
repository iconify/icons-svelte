<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpq5vfbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tpq5vfbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:github-logo-1-solid" {...props}></Icon>
