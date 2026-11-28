<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fys4qbudi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="fys4qbudi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:check-circle-multiple" {...props}></Icon>
