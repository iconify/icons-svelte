<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ieodu4--x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ieodu4--x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:folder-plus" {...props}></Icon>
