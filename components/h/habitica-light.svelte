<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6oqsc4sr.css';
import '../../css/h/h2_b95bkj.css';
import '../../css/m/mz3jy1fyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":76};
const content = `<path class="r6oqsc4sr"/><path class="h2_b95bkj"/><path class="mz3jy1fyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:habitica-light" {...props}></Icon>
