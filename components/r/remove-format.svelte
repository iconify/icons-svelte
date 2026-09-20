<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh3e_4i8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fh3e_4i8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:remove-format" {...props}></Icon>
