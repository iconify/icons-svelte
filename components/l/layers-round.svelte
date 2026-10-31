<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp1jl345l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp1jl345l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:layers-round" {...props}></Icon>
