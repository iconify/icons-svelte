<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-55vfbsm.css';
import '../../css/c/cwu-c8bkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-55vfbsm"/><path class="cwu-c8bkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:fish" {...props}></Icon>
