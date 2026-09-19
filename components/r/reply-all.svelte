<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxkoc6b9e.css';
import '../../css/o/o23x06b7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fxkoc6b9e"/><path class="o23x06b7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:reply-all" {...props}></Icon>
