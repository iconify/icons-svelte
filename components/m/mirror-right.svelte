<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1jl8t0yg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o1jl8t0yg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mirror-right" {...props}></Icon>
