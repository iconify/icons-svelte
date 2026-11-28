<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9khtibqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9khtibqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-dashed-check-solid" {...props}></Icon>
