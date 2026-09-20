<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex850lb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ex850lb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:edit-2-line" {...props}></Icon>
