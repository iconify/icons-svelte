<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqsz9r1ts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qqsz9r1ts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlepreviousempty" {...props}></Icon>
