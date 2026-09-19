<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7sv0zffi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7sv0zffi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-star" {...props}></Icon>
