<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj7e8rbte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pj7e8rbte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-number-4-solid" {...props}></Icon>
