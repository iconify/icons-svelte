<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewoudhbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewoudhbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-2-question" {...props}></Icon>
