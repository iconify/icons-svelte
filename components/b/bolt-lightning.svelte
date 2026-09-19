<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oot6bc-yj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="oot6bc-yj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:bolt-lightning" {...props}></Icon>
