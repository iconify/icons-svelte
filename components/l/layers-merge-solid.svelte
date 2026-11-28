<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhrbp90le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhrbp90le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layers-merge-solid" {...props}></Icon>
