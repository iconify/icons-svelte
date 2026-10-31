<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aemn-9ejj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aemn-9ejj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fast-forward-fill-round" {...props}></Icon>
