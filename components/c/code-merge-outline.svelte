<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7-ct5rft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7-ct5rft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:code-merge-outline" {...props}></Icon>
