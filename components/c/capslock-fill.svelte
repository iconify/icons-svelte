<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqzzpjbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lqzzpjbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:capslock-fill" {...props}></Icon>
