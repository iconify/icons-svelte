<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4_04ubwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4_04ubwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:baby-bottle-solid" {...props}></Icon>
