<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsvpctb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zsvpctb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:infinite-outline" {...props}></Icon>
