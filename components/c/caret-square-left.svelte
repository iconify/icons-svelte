<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmqpj0ysb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="lmqpj0ysb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:caret-square-left" {...props}></Icon>
