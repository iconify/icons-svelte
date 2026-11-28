<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty1yszafl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ty1yszafl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:pizza-star" {...props}></Icon>
