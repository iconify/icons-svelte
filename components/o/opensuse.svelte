<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u99y4pbgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="u99y4pbgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:opensuse" {...props}></Icon>
