<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6xz5ubre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i6xz5ubre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:facebook" {...props}></Icon>
