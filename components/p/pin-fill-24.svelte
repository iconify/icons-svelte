<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5kl9907t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5kl9907t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:pin-fill-24" {...props}></Icon>
