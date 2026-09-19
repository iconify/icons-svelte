<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a66v1g-uz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a66v1g-uz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:message-square-check" {...props}></Icon>
