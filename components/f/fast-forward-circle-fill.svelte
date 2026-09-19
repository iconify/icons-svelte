<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6bpdpb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g6bpdpb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:fast-forward-circle-fill" {...props}></Icon>
