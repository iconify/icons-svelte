<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v40o2_bot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="v40o2_bot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:reactrouter-wordmark" {...props}></Icon>
