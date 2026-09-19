<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk4bk_qwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wk4bk_qwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:aperture" {...props}></Icon>
