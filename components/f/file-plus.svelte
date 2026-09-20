<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhwe4xbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhwe4xbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:file-plus" {...props}></Icon>
