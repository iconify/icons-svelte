<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le5_uo-aa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":960};
const content = `<path class="le5_uo-aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:playvideo" {...props}></Icon>
