<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li7no0b4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="li7no0b4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:email-tick" {...props}></Icon>
