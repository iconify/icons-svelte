<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-m6d5_2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-m6d5_2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-chevron-right-fill-round" {...props}></Icon>
