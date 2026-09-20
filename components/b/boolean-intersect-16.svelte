<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvy7wv0fh.css';
import '../../css/q/qnudf1dbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mvy7wv0fh"/><path clip-rule="evenodd" class="qnudf1dbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:boolean-intersect-16" {...props}></Icon>
