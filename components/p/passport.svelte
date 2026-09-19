<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6xcxzbol.css';
import '../../css/w/wdo02gbao.css';
import '../../css/b/bzea6tsoy.css';
import '../../css/q/qq0d7y3ml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="h6xcxzbol"/><path class="wdo02gbao"/><path class="bzea6tsoy"/><path class="qq0d7y3ml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:passport" {...props}></Icon>
