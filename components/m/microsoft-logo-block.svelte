<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8fiii89q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a8fiii89q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:microsoft-logo-block" {...props}></Icon>
