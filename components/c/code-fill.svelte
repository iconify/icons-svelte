<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apha-ex_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apha-ex_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:code-fill" {...props}></Icon>
