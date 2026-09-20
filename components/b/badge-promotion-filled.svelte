<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6o9acb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c6o9acb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:badge-promotion-filled" {...props}></Icon>
