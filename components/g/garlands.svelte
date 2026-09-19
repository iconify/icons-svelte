<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzt8y6o5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzt8y6o5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:garlands" {...props}></Icon>
