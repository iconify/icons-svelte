<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo585-bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lo585-bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:diary-line" {...props}></Icon>
