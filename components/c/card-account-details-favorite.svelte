<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtg-17b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtg-17b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:card-account-details-favorite" {...props}></Icon>
