<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpw-r42eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":740,"height":700};
const content = `<path class="hpw-r42eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:eye" {...props}></Icon>
