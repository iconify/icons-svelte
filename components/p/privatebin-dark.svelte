<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhgbo5bcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nhgbo5bcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:privatebin-dark" {...props}></Icon>
