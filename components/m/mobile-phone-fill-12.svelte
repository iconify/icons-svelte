<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0tmkpb-w.css';
import '../../css/f/f_i5tj91f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<rect class="g0tmkpb-w"/><path class="f_i5tj91f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:mobile-phone-fill-12" {...props}></Icon>
