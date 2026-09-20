<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa23_2rjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="sa23_2rjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:linux" {...props}></Icon>
