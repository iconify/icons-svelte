<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubfh4dbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubfh4dbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:note-edit-fill-round" {...props}></Icon>
