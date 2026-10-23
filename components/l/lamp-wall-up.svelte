<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz69lobeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gz69lobeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:lamp-wall-up" {...props}></Icon>
