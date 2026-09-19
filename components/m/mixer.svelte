<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj51b5b-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="sj51b5b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:mixer" {...props}></Icon>
