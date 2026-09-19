<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3qi18b3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3qi18b3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-down-left-stroke-circle-filled" {...props}></Icon>
