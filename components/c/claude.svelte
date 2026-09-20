<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epu8qq1sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="epu8qq1sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:claude" {...props}></Icon>
