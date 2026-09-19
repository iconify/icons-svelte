<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1v-qv1cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1v-qv1cv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:folder-minus" {...props}></Icon>
