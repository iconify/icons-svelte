<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rejth40io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rejth40io"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:bluetooth" {...props}></Icon>
