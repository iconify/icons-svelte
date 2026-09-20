<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e00v7ofcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e00v7ofcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:pointer-off" {...props}></Icon>
