<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx-x791iy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sx-x791iy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:arrow-down-large-duotone" {...props}></Icon>
