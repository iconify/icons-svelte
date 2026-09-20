<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf92_rw-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pf92_rw-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bag-minus-outline" {...props}></Icon>
