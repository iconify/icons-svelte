<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbvt85_wv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbvt85_wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:classify-2-line" {...props}></Icon>
