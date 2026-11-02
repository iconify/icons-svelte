<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-c_02b5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-c_02b5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:baby-carriage-fill" {...props}></Icon>
