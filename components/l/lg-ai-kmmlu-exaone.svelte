<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dssyg4bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dssyg4bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lg-ai-kmmlu-exaone" {...props}></Icon>
