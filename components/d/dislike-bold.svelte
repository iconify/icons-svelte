<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljfitzhle.css';
import '../../css/r/r90ig9mfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljfitzhle"/><path class="r90ig9mfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dislike-bold" {...props}></Icon>
