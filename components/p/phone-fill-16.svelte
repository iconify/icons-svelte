<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaw1tfb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qaw1tfb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-fill-16" {...props}></Icon>
