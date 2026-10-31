<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-45c4bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-45c4bfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:command-round" {...props}></Icon>
