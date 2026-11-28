<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vep_7fb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vep_7fb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-right-circle-solid" {...props}></Icon>
