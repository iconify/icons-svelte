<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok25a_71q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ok25a_71q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:all-apps" {...props}></Icon>
