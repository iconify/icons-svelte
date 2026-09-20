<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5uhekmkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5uhekmkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-turn-back-fill" {...props}></Icon>
