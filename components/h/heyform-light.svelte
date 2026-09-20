<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0etpyb4l.css';
import '../../css/d/dkp-fpbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c0etpyb4l"/><path class="dkp-fpbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:heyform-light" {...props}></Icon>
