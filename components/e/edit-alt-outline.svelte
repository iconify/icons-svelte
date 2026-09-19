<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-w7s1bmt.css';
import '../../css/y/ys8pa0b4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z-w7s1bmt"/><path class="ys8pa0b4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:edit-alt-outline" {...props}></Icon>
