<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt6fivdvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt6fivdvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-up-lg" {...props}></Icon>
