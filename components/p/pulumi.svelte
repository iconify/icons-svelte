<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqy19wbvc.css';
import '../../css/q/qe0d046kd.css';
import '../../css/a/atzomcwel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":271};
const content = `<path class="cqy19wbvc"/><path class="qe0d046kd"/><path class="atzomcwel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pulumi" {...props}></Icon>
