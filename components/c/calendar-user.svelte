<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o053b3bvz.css';
import '../../css/u/u2os-ab_w.css';
import '../../css/n/n6lpwabqu.css';
import '../../css/n/n-dzcccws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o053b3bvz"/><path class="u2os-ab_w"/><path class="n6lpwabqu"/><path class="n-dzcccws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:calendar-user" {...props}></Icon>
