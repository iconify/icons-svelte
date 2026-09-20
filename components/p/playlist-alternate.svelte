<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7cv9nkec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7cv9nkec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:playlist-alternate" {...props}></Icon>
