<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qeztyrbbn.css';
import '../../css/u/uen6t6bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qeztyrbbn"/><path class="uen6t6bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:reach" {...props}></Icon>
