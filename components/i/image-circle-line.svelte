<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_e_8cb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_e_8cb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:image-circle-line" {...props}></Icon>
