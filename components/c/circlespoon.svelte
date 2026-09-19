<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imi44z7-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="imi44z7-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlespoon" {...props}></Icon>
