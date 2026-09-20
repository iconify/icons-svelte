<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eshlbnbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eshlbnbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:perplexity-fill" {...props}></Icon>
