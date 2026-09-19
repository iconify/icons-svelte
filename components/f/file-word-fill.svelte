<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb5zndzyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vb5zndzyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-word-fill" {...props}></Icon>
