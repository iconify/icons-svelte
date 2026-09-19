<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byk5dy4fd.css';
import '../../css/b/b4d3mc68f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="byk5dy4fd"/><path class="b4d3mc68f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:passenger-plus" {...props}></Icon>
