<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3ce1jl_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3ce1jl_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:popout" {...props}></Icon>
