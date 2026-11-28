<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg96uj61p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg96uj61p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-number-1-solid" {...props}></Icon>
