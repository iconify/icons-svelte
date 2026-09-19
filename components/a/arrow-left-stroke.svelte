<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq-4ibcwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aq-4ibcwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-left-stroke" {...props}></Icon>
