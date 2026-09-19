<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f01n6jbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f01n6jbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pointing-right-08" {...props}></Icon>
