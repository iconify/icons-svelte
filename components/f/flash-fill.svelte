<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlb_45vzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlb_45vzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:flash-fill" {...props}></Icon>
