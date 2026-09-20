<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps6co1fpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ps6co1fpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-square" {...props}></Icon>
