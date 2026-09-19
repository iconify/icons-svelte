<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyb0b6a3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyb0b6a3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-big-down" {...props}></Icon>
