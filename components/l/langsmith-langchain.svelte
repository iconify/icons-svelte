<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpa2erboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpa2erboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:langsmith-langchain" {...props}></Icon>
