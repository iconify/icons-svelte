<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbzoj2bix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbzoj2bix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:mixx-logo-solid" {...props}></Icon>
