<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4b9-dbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4b9-dbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-brake-parking" {...props}></Icon>
