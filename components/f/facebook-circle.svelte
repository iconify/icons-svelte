<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw_-6tbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gw_-6tbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:facebook-circle" {...props}></Icon>
