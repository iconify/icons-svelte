<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/codjm1acu.css';
import '../../css/h/hcbe-gbff.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="codjm1acu"/><path class="hcbe-gbff"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-sweden" {...props}></Icon>
