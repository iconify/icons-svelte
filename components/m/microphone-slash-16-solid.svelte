<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq42nebwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mq42nebwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:microphone-slash-16-solid" {...props}></Icon>
