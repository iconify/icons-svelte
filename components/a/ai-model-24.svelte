<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw6cgiv-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vw6cgiv-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:ai-model-24" {...props}></Icon>
