<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5vf289bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r5vf289bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-help-empty" {...props}></Icon>
