<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux5dqullz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux5dqullz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-copy-alt-outline" {...props}></Icon>
