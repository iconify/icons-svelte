<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6a346guy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6a346guy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-forward-square-15-line" {...props}></Icon>
