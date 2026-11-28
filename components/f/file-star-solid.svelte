<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khl0h4dia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khl0h4dia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-star-solid" {...props}></Icon>
