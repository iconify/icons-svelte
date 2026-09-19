<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3gqadqms.css';
import '../../css/x/x1cgi72hj.css';
import '../../css/b/bp6uewcuv.css';
import '../../css/o/o-yxj2bfk.css';
import '../../css/a/adbgsmbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="t3gqadqms"/><path class="x1cgi72hj"/><path clip-rule="evenodd" class="bp6uewcuv"/><path clip-rule="evenodd" class="o-yxj2bfk"/><path class="adbgsmbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:huggingface" {...props}></Icon>
