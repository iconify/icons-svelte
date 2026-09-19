<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv08i_bqv.css';
import '../../css/s/s1o53nbht.css';
import '../../css/q/qkn998sep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sv08i_bqv"/><path class="s1o53nbht"/><path class="qkn998sep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:circle-stack-16-solid" {...props}></Icon>
