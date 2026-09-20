<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn43otbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cn43otbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-2-up" {...props}></Icon>
