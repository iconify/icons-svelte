<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-b0mvb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-b0mvb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:maintenance" {...props}></Icon>
