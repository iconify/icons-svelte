<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p44ku7_ie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p44ku7_ie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:keyboard" {...props}></Icon>
