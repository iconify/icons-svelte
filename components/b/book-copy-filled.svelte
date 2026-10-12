<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2nr3_bdv.css';
import '../../css/t/tkgm1jb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2nr3_bdv"/><path clip-rule="evenodd" class="tkgm1jb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:book-copy-filled" {...props}></Icon>
