<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-7edqb5i.css';
import '../../css/f/fm7fqi_re.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/d/dvtlueb-w.css';
import '../../css/w/wwq-3qbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="z-7edqb5i"/><path class="fm7fqi_re"/><g class="jn8qy4bru"><path class="dvtlueb-w"/><path class="wwq-3qbpu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:closed-book" {...props}></Icon>
