<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbv-3pwvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbv-3pwvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:crown-a-fill" {...props}></Icon>
