<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl5w8z7ax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xl5w8z7ax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:equalizer" {...props}></Icon>
