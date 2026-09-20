<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/n/n6v75b2-j.css';
import '../../css/n/nb1e76c9o.css';
import '../../css/m/m7inagr1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="n6v75b2-j"/><path class="nb1e76c9o"/><path class="m7inagr1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:chicken-grilled-stream-flat" {...props}></Icon>
