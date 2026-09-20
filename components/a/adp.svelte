<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa5fcwjiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa5fcwjiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:adp" {...props}></Icon>
