<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrb6phh1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vrb6phh1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:pinpoint" {...props}></Icon>
