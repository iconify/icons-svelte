<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okr-h6u1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="okr-h6u1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:bar-code-16" {...props}></Icon>
