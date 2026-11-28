<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks-jpshjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks-jpshjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-number-7-solid" {...props}></Icon>
