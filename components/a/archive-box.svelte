<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_hlqh4vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_hlqh4vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:archive-box" {...props}></Icon>
