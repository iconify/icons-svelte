<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b__i1vbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="b__i1vbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:nas" {...props}></Icon>
