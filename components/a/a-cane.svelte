<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcyq5-6nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jcyq5-6nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:a-cane" {...props}></Icon>
