<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or7lffclf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or7lffclf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hotkey-line" {...props}></Icon>
