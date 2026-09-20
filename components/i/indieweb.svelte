<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs4jkg62j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fs4jkg62j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:indieweb" {...props}></Icon>
