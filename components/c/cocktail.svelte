<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjpoa93vo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="xjpoa93vo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:cocktail" {...props}></Icon>
