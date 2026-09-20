<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlmp9xaqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlmp9xaqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-to-up-line" {...props}></Icon>
