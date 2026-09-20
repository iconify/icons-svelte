<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm7fgh3tp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bm7fgh3tp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-right-circle-fill" {...props}></Icon>
