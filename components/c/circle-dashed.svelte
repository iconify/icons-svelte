<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfox6fcqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfox6fcqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:circle-dashed" {...props}></Icon>
