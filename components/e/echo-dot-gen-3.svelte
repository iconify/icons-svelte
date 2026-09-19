<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my5dueb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="my5dueb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:echo-dot-gen-3" {...props}></Icon>
