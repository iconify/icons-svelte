<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj1gwlbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aj1gwlbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-office-presentation-light" {...props}></Icon>
