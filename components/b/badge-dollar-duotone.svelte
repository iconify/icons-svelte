<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyospdzkg.css';
import '../../css/r/r5r1i95ve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyospdzkg"/><path class="r5r1i95ve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:badge-dollar-duotone" {...props}></Icon>
