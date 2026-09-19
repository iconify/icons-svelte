<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-8k04oul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-8k04oul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:port" {...props}></Icon>
