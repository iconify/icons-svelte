<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hat5ykuoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="hat5ykuoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:notes-medical" {...props}></Icon>
