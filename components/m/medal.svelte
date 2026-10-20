<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kscjx21xy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kscjx21xy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:medal" {...props}></Icon>
