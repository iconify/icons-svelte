<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn_zxdbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jn_zxdbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:ballerina-wordmark" {...props}></Icon>
