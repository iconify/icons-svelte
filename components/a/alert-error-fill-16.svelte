<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmztkp8jx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qmztkp8jx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:alert-error-fill-16" {...props}></Icon>
