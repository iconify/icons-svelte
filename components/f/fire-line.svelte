<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zip9yv1tu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zip9yv1tu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fire-line" {...props}></Icon>
