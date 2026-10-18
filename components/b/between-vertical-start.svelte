<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owo73fbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owo73fbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:between-vertical-start" {...props}></Icon>
