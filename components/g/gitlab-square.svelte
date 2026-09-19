<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyx1o4bkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cyx1o4bkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:gitlab-square" {...props}></Icon>
