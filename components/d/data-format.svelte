<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9vtyyb-e.css';
import '../../css/c/ca5ecz53l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u9vtyyb-e"/><path class="ca5ecz53l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-format" {...props}></Icon>
