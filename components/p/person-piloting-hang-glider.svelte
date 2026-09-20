<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg-9uhmgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qg-9uhmgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-piloting-hang-glider" {...props}></Icon>
