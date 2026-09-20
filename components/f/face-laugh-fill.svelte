<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6900q75u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6900q75u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:face-laugh-fill" {...props}></Icon>
