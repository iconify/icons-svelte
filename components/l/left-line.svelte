<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emwij-b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emwij-b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:left-line" {...props}></Icon>
