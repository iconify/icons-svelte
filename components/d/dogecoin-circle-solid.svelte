<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxrn3rb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uxrn3rb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:dogecoin-circle-solid" {...props}></Icon>
