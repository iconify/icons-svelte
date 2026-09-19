<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4yav7kxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4yav7kxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-down-left-stroke-filled" {...props}></Icon>
