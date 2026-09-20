<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snt3n6ezt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snt3n6ezt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-brake-retarder" {...props}></Icon>
