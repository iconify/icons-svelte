<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olg2t05yp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":666};
const content = `<path class="olg2t05yp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:github" {...props}></Icon>
