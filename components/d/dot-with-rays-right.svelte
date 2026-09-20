<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otiao8vie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="otiao8vie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dot-with-rays-right" {...props}></Icon>
