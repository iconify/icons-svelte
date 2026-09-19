<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk9y8_tpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="pk9y8_tpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:lines-leaning" {...props}></Icon>
