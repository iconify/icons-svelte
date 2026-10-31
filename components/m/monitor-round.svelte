<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt9su1b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gt9su1b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:monitor-round" {...props}></Icon>
