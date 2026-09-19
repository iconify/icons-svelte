<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6mmipbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":922,"height":622};
const content = `<path class="g6mmipbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:bicycle" {...props}></Icon>
