<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct14smb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct14smb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:clock-gear" {...props}></Icon>
