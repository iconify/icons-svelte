<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4_jl3lxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="c4_jl3lxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:battery-half-f" {...props}></Icon>
