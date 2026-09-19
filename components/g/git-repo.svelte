<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzrh2j4yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jzrh2j4yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:git-repo" {...props}></Icon>
