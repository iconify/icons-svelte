<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g24t70bvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g24t70bvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-open-fill" {...props}></Icon>
