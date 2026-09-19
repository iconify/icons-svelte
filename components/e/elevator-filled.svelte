<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2-y3rb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2-y3rb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:elevator-filled" {...props}></Icon>
