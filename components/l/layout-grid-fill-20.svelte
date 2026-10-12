<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z387mc50s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z387mc50s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:layout-grid-fill-20" {...props}></Icon>
