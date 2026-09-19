<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqy7qnh-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kqy7qnh-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:actn" {...props}></Icon>
