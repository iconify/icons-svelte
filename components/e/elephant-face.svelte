<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0niglb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0niglb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:elephant-face" {...props}></Icon>
