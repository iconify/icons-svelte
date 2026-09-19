<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9qxpacjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9qxpacjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-down-right-stroke-filled" {...props}></Icon>
