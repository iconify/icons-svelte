<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcpgq_b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcpgq_b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:oreilly" {...props}></Icon>
