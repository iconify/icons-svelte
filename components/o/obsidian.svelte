<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/err9aob5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="err9aob5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:obsidian" {...props}></Icon>
