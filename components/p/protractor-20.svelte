<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cugs406to.css';
import '../../css/z/zrzrd2cbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cugs406to"/><path class="zrzrd2cbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:protractor-20" {...props}></Icon>
