<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1r9nnbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1r9nnbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:folder-plus" {...props}></Icon>
