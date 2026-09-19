<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_e53vbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="y_e53vbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:fish" {...props}></Icon>
