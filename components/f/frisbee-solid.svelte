<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znuu2hcur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znuu2hcur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:frisbee-solid" {...props}></Icon>
