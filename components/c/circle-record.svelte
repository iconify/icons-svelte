<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh4zjm5am.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xh4zjm5am"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-record" {...props}></Icon>
