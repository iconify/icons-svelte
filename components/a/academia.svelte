<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw7w3hc8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="xw7w3hc8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:academia" {...props}></Icon>
