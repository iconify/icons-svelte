<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhpxstb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhpxstb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:pumpkin" {...props}></Icon>
