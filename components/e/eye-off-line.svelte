<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5j902m7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5j902m7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:eye-off-line" {...props}></Icon>
