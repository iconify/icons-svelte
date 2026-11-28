<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt3xv6jin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gt3xv6jin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clock-9" {...props}></Icon>
