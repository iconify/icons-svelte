<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-w3vmb5c.css';
import '../../css/m/m97pomy2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-w3vmb5c"/><path clip-rule="evenodd" class="m97pomy2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:d3d" {...props}></Icon>
