<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq3z381fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jq3z381fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-trending-down" {...props}></Icon>
