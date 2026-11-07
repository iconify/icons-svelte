<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbotjw3iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbotjw3iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:face-id" {...props}></Icon>
