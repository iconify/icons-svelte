<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nogaml5-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nogaml5-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:factory-fill-round" {...props}></Icon>
