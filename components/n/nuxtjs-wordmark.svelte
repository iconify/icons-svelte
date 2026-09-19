<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaspbr6si.css';
import '../../css/f/f6jk9u_pw.css';
import '../../css/j/j813l0n6f.css';
import '../../css/d/d2kvgvbvc.css';
import '../../css/c/cczuxwb0a.css';
import '../../css/j/jk5rd7bma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zaspbr6si"/><path class="f6jk9u_pw"/><path class="j813l0n6f"/><g class="d2kvgvbvc"><path class="cczuxwb0a"/><path class="jk5rd7bma"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nuxtjs-wordmark" {...props}></Icon>
