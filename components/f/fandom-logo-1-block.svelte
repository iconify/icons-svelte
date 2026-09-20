<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_m1lbgnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q_m1lbgnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:fandom-logo-1-block" {...props}></Icon>
