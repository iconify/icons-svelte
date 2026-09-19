<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aboyzwb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aboyzwb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chart-pie-alt-02-filled" {...props}></Icon>
