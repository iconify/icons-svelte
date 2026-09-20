<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocaehubvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ocaehubvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:align-center" {...props}></Icon>
