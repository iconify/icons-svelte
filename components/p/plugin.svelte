<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnjstib_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cnjstib_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:plugin" {...props}></Icon>
