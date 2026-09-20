<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4p1ucc9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4p1ucc9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:briefcase-upload-outline" {...props}></Icon>
