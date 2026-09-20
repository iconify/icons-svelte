<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/o/ovjojutqj.css';
import '../../css/e/eh7hbn4kn.css';
import '../../css/k/khmubjb4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="ovjojutqj"/><path class="eh7hbn4kn"/><path class="khmubjb4h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:megaphone" {...props}></Icon>
