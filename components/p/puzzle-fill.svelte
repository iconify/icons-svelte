<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7yio4ctw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a7yio4ctw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:puzzle-fill" {...props}></Icon>
