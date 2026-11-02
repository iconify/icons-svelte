<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iffe5zl0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iffe5zl0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:maya-pyramids-line" {...props}></Icon>
