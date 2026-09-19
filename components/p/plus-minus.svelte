<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyei0ydwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="yyei0ydwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:plus-minus" {...props}></Icon>
