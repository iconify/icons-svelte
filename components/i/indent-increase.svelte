<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdaunkhqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hdaunkhqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:indent-increase" {...props}></Icon>
