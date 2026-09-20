<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au72xp_dp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au72xp_dp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:avm" {...props}></Icon>
