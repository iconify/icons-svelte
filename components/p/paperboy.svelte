<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7j0lof8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":720};
const content = `<path class="h7j0lof8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:paperboy" {...props}></Icon>
