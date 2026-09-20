<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvho9y7-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvho9y7-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:megaphone-line" {...props}></Icon>
