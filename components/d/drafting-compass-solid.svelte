<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr7p-mbpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yr7p-mbpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:drafting-compass-solid" {...props}></Icon>
