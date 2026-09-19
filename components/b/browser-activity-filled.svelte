<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-ymmcboc.css';
import '../../css/f/fxadkqblw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-ymmcboc"/><path class="fxadkqblw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:browser-activity-filled" {...props}></Icon>
