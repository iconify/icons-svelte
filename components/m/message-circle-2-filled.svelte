<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krw0w3bug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krw0w3bug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-circle-2-filled" {...props}></Icon>
