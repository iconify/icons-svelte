<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcf4q5osf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lcf4q5osf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-o-box-outline" {...props}></Icon>
