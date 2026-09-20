<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6yng8mpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h6yng8mpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:checkup-medical-report-clipboard-remix" {...props}></Icon>
