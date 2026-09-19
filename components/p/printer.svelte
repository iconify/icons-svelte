<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4yu1bgbf.css';
import '../../css/j/jo-ewmbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4yu1bgbf"/><path class="jo-ewmbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:printer" {...props}></Icon>
