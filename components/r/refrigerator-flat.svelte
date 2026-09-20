<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/f/fa1-jbcbc.css';
import '../../css/t/tg05lba0t.css';
import '../../css/q/qtekbtbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="fa1-jbcbc"/><path class="tg05lba0t"/><path class="qtekbtbjg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:refrigerator-flat" {...props}></Icon>
