<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8romb68f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="o8romb68f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:note-forward" {...props}></Icon>
