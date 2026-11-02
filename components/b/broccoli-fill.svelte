<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzv1a3tvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzv1a3tvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:broccoli-fill" {...props}></Icon>
