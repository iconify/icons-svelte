<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzbzo6yfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tzbzo6yfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:border-style" {...props}></Icon>
