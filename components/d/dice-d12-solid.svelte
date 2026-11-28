<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxeq4xbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxeq4xbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:dice-d12-solid" {...props}></Icon>
