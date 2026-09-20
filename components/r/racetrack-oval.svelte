<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy0hk4bne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hy0hk4bne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:racetrack-oval" {...props}></Icon>
