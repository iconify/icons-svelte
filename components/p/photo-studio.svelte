<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/k/ko4kphb8z.css';
import '../../css/z/z2i083byh.css';
import '../../css/a/a6wkvlbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="ko4kphb8z"/><path class="z2i083byh"/><path class="a6wkvlbgd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:photo-studio" {...props}></Icon>
