<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9_9czbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9_9czbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:music-alternate-fill" {...props}></Icon>
