<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3vic4b4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3vic4b4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:fire-a-fill" {...props}></Icon>
