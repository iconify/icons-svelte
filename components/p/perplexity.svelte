<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t48jsfxwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t48jsfxwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:perplexity" {...props}></Icon>
