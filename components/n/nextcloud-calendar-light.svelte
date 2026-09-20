<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3znd9b4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n3znd9b4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-calendar-light" {...props}></Icon>
