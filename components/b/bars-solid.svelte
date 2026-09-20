<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke89ayr1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ke89ayr1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:bars-solid" {...props}></Icon>
