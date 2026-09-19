<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgebjd7_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgebjd7_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:house-01" {...props}></Icon>
