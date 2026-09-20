<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig5m35nvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ig5m35nvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:notification-bell-plus-fill" {...props}></Icon>
