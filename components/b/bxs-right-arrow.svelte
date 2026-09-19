<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajl4pv1wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajl4pv1wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-right-arrow" {...props}></Icon>
