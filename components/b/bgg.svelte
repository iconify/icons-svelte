<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6p7jc9_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="o6p7jc9_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:bgg" {...props}></Icon>
