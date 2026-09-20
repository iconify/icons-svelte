<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j89vr6sxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j89vr6sxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:mobile-me-logo-solid" {...props}></Icon>
