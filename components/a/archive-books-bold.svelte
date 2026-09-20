<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey-ae8pml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ey-ae8pml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:archive-books-bold" {...props}></Icon>
