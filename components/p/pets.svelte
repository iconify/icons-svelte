<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9ng8-b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u9ng8-b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:pets" {...props}></Icon>
