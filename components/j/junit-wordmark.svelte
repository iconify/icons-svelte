<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl5yxuxbb.css';
import '../../css/q/qpw537-7f.css';
import '../../css/o/omvhn6b9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zl5yxuxbb"/><path class="qpw537-7f"/><path class="omvhn6b9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:junit-wordmark" {...props}></Icon>
