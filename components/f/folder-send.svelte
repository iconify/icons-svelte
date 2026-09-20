<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z411kfbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z411kfbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folder-send" {...props}></Icon>
