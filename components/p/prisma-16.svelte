<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcrk4e8vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qcrk4e8vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:prisma-16" {...props}></Icon>
