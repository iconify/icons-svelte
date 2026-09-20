<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q51zqjkxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":12};
const content = `<path class="q51zqjkxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:ltr" {...props}></Icon>
