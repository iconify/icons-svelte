<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/f/fiuzy_whq.css';
import '../../css/i/i5mj2xiuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="fiuzy_whq"/><path class="i5mj2xiuf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:money-bag" {...props}></Icon>
