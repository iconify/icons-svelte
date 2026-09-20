<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8710zbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8710zbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:apl" {...props}></Icon>
