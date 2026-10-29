<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i80tytbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i80tytbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bot-message-square-solid" {...props}></Icon>
