<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2b2h7b3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2b2h7b3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:battery" {...props}></Icon>
