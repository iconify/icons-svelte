<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oivi-4bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oivi-4bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-circle-check-round" {...props}></Icon>
