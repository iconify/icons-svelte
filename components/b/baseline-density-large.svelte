<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0s5e9nnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0s5e9nnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:baseline-density-large" {...props}></Icon>
