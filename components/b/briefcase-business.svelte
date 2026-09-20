<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv89s0poi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv89s0poi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:briefcase-business" {...props}></Icon>
