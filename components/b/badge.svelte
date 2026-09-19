<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xar5kfbwv.css';
import '../../css/c/c36bb3bek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xar5kfbwv"/><path class="c36bb3bek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:badge" {...props}></Icon>
