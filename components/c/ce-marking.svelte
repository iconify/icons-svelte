<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwvishnme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uwvishnme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:ce-marking" {...props}></Icon>
