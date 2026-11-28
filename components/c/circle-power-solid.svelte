<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aynsa_bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aynsa_bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-power-solid" {...props}></Icon>
