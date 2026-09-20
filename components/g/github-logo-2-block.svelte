<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yct-3_m9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yct-3_m9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:github-logo-2-block" {...props}></Icon>
