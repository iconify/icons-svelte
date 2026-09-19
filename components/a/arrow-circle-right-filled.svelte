<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un8mlebwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="un8mlebwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:arrow-circle-right-filled" {...props}></Icon>
