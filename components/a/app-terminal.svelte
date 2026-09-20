<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh76tebbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kh76tebbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:app-terminal" {...props}></Icon>
