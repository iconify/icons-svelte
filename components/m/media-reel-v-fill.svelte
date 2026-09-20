<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0yfsub-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0yfsub-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:media-reel-v-fill" {...props}></Icon>
