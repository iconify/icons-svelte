<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0_dibbns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h0_dibbns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folders-line" {...props}></Icon>
