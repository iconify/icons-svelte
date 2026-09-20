<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsaax2ben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsaax2ben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:phone-outgoing-line" {...props}></Icon>
