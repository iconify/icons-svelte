<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1dgm2ptv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x1dgm2ptv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bus-mini-filled" {...props}></Icon>
