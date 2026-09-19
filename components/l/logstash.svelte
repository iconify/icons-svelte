<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oopsgunny.css';
import '../../css/e/eq6f2obhm.css';
import '../../css/u/uxyj568bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="oopsgunny"/><path class="eq6f2obhm"/><path class="uxyj568bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:logstash" {...props}></Icon>
