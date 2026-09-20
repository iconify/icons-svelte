<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/b43l1ybzt.css';
import '../../css/e/ei21x3heb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path clip-rule="evenodd" class="b43l1ybzt"/><path class="ei21x3heb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:commanda-cohere" {...props}></Icon>
