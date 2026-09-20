<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkzbjcb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkzbjcb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:command-off" {...props}></Icon>
