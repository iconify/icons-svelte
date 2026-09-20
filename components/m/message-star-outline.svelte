<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm46kiyup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cm46kiyup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:message-star-outline" {...props}></Icon>
