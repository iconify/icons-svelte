<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nakbmvbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nakbmvbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-briefcase" {...props}></Icon>
