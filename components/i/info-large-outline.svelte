<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cium_fbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cium_fbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:info-large-outline" {...props}></Icon>
