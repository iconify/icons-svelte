<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmi-m1byp.css';
import '../../css/w/wabkv5x6c.css';
import '../../css/f/f6j6ebcpk.css';
import '../../css/a/a9480j_gl.css';
import '../../css/j/jpuqzh8by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zmi-m1byp"/><path class="wabkv5x6c"/><path class="f6j6ebcpk"/><path class="a9480j_gl"/><path class="jpuqzh8by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:barberpole" {...props}></Icon>
