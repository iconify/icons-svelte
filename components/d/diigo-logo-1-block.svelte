<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl_azmknv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jl_azmknv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:diigo-logo-1-block" {...props}></Icon>
