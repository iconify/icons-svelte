<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu221abpe.css';
import '../../css/r/r4hkkkb6r.css';
import '../../css/i/iq67862zl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eu221abpe"/><path class="r4hkkkb6r"/><path class="iq67862zl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:acorn" {...props}></Icon>
