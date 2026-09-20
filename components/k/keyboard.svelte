<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/artlz7bym.css';
import '../../css/c/c5y_3_b0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="artlz7bym"/><path class="c5y_3_b0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:keyboard" {...props}></Icon>
