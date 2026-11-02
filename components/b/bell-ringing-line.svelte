<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7cb2zbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7cb2zbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bell-ringing-line" {...props}></Icon>
