<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdjb4f5fe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdjb4f5fe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-compare-fill" {...props}></Icon>
