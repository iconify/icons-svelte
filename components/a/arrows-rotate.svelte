<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjuz5xywi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjuz5xywi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:arrows-rotate" {...props}></Icon>
