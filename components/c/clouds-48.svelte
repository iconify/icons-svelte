<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh7k9xbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eh7k9xbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clouds-48" {...props}></Icon>
