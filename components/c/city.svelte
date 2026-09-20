<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqc13dx2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uqc13dx2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:city" {...props}></Icon>
