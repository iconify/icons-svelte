<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6j-kt1ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h6j-kt1ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:earlybirds" {...props}></Icon>
