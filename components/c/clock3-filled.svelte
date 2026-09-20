<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl_omuber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jl_omuber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:clock3-filled" {...props}></Icon>
