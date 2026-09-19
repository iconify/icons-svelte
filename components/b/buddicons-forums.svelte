<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o516ekcpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o516ekcpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:buddicons-forums" {...props}></Icon>
