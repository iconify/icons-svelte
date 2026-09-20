<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxo0fczcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wxo0fczcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:osticket-dark" {...props}></Icon>
