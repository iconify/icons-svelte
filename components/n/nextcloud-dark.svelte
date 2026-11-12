<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxy3eibvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nxy3eibvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-dark" {...props}></Icon>
