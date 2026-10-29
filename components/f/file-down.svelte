<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0yoxtbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0yoxtbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-down" {...props}></Icon>
