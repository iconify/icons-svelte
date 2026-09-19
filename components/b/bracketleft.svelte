<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2n0ttdhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":168,"height":954};
const content = `<path class="c2n0ttdhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:bracketleft" {...props}></Icon>
