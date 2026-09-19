<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dih2-uk2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="dih2-uk2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:goforward" {...props}></Icon>
