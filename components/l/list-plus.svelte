<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3i9c38fh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3i9c38fh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:list-plus" {...props}></Icon>
