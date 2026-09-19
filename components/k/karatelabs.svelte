<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypy0npbna.css';
import '../../css/g/g0uat02ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ypy0npbna"/><path class="g0uat02ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:karatelabs" {...props}></Icon>
