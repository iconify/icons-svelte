<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3jl3kb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t3jl3kb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-left-start-on-rectangle-solid" {...props}></Icon>
