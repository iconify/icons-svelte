<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yaafqclde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yaafqclde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-checkmark-circle-outline" {...props}></Icon>
