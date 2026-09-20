<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iawrygbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iawrygbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:apple-keyboard-command" {...props}></Icon>
