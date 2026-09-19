<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceatd5b9s.css';
import '../../css/w/w6jecwb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ceatd5b9s"/><path class="w6jecwb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:done-all-fill" {...props}></Icon>
