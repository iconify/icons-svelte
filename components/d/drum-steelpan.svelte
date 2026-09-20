<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xua8f1yhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xua8f1yhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:drum-steelpan" {...props}></Icon>
