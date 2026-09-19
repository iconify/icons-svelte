<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf6coj27j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lf6coj27j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:dgb" {...props}></Icon>
