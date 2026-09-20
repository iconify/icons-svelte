<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl91_bbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jl91_bbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:field-corner-kick-bold" {...props}></Icon>
