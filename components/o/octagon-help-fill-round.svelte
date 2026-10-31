<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2ok6dbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2ok6dbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:octagon-help-fill-round" {...props}></Icon>
