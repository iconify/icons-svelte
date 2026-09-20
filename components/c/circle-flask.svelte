<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j149s87aw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="j149s87aw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:circle-flask" {...props}></Icon>
