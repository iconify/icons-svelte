<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbh-40nht.css';
import '../../css/j/jze6f0ytj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lbh-40nht"/><path class="jze6f0ytj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:id-badge-16" {...props}></Icon>
