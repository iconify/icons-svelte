<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcn1mjbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="qcn1mjbjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:data-arrow-down" {...props}></Icon>
