<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfy9ylpub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfy9ylpub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:honey-outline" {...props}></Icon>
