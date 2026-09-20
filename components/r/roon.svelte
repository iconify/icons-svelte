<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah766zb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ah766zb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:roon" {...props}></Icon>
