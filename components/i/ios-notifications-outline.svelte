<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzcjqdbir.css';
import '../../css/u/upwfrwbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jzcjqdbir"/><path class="upwfrwbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-notifications-outline" {...props}></Icon>
