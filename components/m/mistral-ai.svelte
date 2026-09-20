<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm6ttwbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm6ttwbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:mistral-ai" {...props}></Icon>
