<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clg13_kjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="clg13_kjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:blur-linear" {...props}></Icon>
