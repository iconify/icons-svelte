<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h96ml7bnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h96ml7bnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:dots-horizontal-rounded" {...props}></Icon>
