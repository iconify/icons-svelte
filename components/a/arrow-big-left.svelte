<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6-4dugws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6-4dugws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-big-left" {...props}></Icon>
