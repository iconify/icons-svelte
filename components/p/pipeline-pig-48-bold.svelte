<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/engaw8bgi.css';
import '../../css/l/lsh_8pjho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="engaw8bgi"/><path class="lsh_8pjho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipeline-pig-48-bold" {...props}></Icon>
