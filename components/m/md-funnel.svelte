<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmq4v6njp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cmq4v6njp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-funnel" {...props}></Icon>
