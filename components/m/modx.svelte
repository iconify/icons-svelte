<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhl70gudo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zhl70gudo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:modx" {...props}></Icon>
