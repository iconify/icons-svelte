<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgbr6jg2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="mgbr6jg2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:close-outline" {...props}></Icon>
