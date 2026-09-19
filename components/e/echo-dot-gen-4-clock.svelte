<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm7s0jbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nm7s0jbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:echo-dot-gen-4-clock" {...props}></Icon>
