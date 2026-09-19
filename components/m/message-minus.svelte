<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu1a9m03i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu1a9m03i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:message-minus" {...props}></Icon>
