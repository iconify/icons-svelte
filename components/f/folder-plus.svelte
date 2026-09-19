<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec49kjbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ec49kjbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:folder-plus" {...props}></Icon>
