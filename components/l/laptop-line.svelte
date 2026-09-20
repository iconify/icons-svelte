<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejaot-bbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejaot-bbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:laptop-line" {...props}></Icon>
