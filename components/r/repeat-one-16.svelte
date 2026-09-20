<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b572sebbf.css';
import '../../css/s/sqgcj3ezp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b572sebbf"/><path class="sqgcj3ezp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:repeat-one-16" {...props}></Icon>
