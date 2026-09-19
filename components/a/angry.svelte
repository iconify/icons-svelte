<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9mby9bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="e9mby9bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:angry" {...props}></Icon>
