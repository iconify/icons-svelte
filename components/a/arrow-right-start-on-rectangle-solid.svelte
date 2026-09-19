<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inbfl_ipd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="inbfl_ipd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-right-start-on-rectangle-solid" {...props}></Icon>
