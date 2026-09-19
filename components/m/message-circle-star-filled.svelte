<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g35v4-zfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g35v4-zfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-circle-star-filled" {...props}></Icon>
