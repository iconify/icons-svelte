<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx6kogx4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zx6kogx4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:broom-motion-fill" {...props}></Icon>
