<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob72q5bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ob72q5bva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:camper-trailer-dump" {...props}></Icon>
