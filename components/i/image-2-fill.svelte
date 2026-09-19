<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4a0zvbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4a0zvbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:image-2-fill" {...props}></Icon>
