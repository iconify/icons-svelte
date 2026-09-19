<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il392qm0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="il392qm0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:greater-than" {...props}></Icon>
