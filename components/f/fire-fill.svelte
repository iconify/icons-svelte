<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nybkktbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nybkktbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fire-fill" {...props}></Icon>
