<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfdq1hqyb.css';
import '../../css/b/b_1t8ab1f.css';
import '../../css/p/pu2xhg2fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="kfdq1hqyb"/><path class="b_1t8ab1f"/><path class="pu2xhg2fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:kibana" {...props}></Icon>
