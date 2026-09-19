<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5q9z5bbs.css';
import '../../css/v/vvasjdjcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o5q9z5bbs"/><path class="vvasjdjcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:color" {...props}></Icon>
