<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh4wrolxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":512};
const content = `<path class="mh4wrolxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:bonnet" {...props}></Icon>
