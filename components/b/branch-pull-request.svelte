<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avxsj4pan.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="avxsj4pan"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:branch-pull-request" {...props}></Icon>
