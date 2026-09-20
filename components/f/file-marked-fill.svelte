<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frdzy3b5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frdzy3b5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-marked-fill" {...props}></Icon>
