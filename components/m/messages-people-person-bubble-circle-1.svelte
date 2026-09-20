<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrrckuble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrrckuble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:messages-people-person-bubble-circle-1" {...props}></Icon>
