<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnts40jnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnts40jnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:headset-fill-round" {...props}></Icon>
