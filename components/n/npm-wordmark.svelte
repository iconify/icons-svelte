<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qczyu4bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qczyu4bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:npm-wordmark" {...props}></Icon>
