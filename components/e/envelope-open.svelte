<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfexy_bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfexy_bin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:envelope-open" {...props}></Icon>
