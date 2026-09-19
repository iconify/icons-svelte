<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzxasfbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yzxasfbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:baseball-bat" {...props}></Icon>
