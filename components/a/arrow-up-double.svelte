<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ityo7fbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ityo7fbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-up-double" {...props}></Icon>
