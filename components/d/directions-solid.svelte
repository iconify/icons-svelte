<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izg17ge-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izg17ge-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:directions-solid" {...props}></Icon>
