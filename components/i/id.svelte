<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2k_9ab2j.css';
import '../../css/b/bfvbc4b-j.css';
import '../../css/h/hz6ugwsiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c2k_9ab2j"/><path class="bfvbc4b-j"/><path class="hz6ugwsiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:id" {...props}></Icon>
