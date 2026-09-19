<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c76i_ob0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c76i_ob0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bag-plus-fill" {...props}></Icon>
