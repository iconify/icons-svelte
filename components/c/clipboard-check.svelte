<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y48v3sbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="y48v3sbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:clipboard-check" {...props}></Icon>
