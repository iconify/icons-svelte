<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojcv45blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ojcv45blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chirpy-light" {...props}></Icon>
