<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unzlyb_8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unzlyb_8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:exclamation-circle-fill" {...props}></Icon>
