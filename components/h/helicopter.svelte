<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf_d8cagc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hf_d8cagc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:helicopter" {...props}></Icon>
