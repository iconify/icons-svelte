<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nycwa6btp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nycwa6btp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:chevron-up" {...props}></Icon>
