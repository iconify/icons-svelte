<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiq2jf6xu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oiq2jf6xu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:asana-solid" {...props}></Icon>
