<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjy379omm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjy379omm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:circle-dashed" {...props}></Icon>
