<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl8wdhw6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jl8wdhw6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:quote" {...props}></Icon>
