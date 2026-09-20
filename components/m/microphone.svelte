<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8q-aybpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="u8q-aybpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:microphone" {...props}></Icon>
