<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njeis7bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njeis7bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:office-building-plus-outline" {...props}></Icon>
