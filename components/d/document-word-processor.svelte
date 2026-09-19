<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6gjfe24p.css';
import '../../css/r/r4tc83xlk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r6gjfe24p"/><path class="r4tc83xlk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-word-processor" {...props}></Icon>
