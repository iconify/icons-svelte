<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5xf04bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s5xf04bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:basketswing" {...props}></Icon>
