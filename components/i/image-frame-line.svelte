<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g85wt0b1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g85wt0b1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:image-frame-line" {...props}></Icon>
