<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijl3j-lgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ijl3j-lgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:play-outline" {...props}></Icon>
