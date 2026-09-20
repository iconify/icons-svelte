<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugcq4-b9s.css';
import '../../css/s/s-czd34rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":82.6,"height":82.6};
const content = `<circle class="ugcq4-b9s"/><path class="s-czd34rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:litecoin" {...props}></Icon>
