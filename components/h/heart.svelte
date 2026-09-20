<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfwt8_btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfwt8_btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:heart" {...props}></Icon>
