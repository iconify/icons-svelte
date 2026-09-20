<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/c/cqiqivb9n.css';
import '../../css/v/vkw7rqb2f.css';
import '../../css/t/tos-6mbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="cqiqivb9n"/><path class="vkw7rqb2f"/><path class="tos-6mbrd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:clock" {...props}></Icon>
