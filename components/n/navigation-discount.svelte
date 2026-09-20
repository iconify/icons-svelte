<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl8jdu0bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jl8jdu0bj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:navigation-discount" {...props}></Icon>
