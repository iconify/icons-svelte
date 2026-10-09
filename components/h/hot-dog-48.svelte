<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay0q9u-4z.css';
import '../../css/q/q4-w0wbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ay0q9u-4z"/><path class="q4-w0wbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hot-dog-48" {...props}></Icon>
