<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5x-7fbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5x-7fbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-right-left" {...props}></Icon>
