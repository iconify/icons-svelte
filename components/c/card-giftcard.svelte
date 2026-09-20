<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygfg23b1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygfg23b1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:card-giftcard" {...props}></Icon>
