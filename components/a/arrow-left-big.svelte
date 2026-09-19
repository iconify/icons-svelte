<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-ctoglml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-ctoglml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-left-big" {...props}></Icon>
