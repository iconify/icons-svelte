<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r16t1096v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r16t1096v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:flux" {...props}></Icon>
