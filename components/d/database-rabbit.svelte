<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-0iu1ivl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q-0iu1ivl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:database-rabbit" {...props}></Icon>
