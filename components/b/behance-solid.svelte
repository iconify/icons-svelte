<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5-r2cb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="q5-r2cb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:behance-solid" {...props}></Icon>
