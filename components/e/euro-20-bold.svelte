<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptysfhbch.css';
import '../../css/g/ge6al85qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ptysfhbch"/><path class="ge6al85qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:euro-20-bold" {...props}></Icon>
