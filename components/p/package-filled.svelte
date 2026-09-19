<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5v0brb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5v0brb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:package-filled" {...props}></Icon>
