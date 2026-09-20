<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obbl1ynnb.css';
import '../../css/j/jj_lj5bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="obbl1ynnb"/><path class="jj_lj5bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-docs-light" {...props}></Icon>
