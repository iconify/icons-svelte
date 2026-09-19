<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgj0q-b2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jgj0q-b2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:folder-conversion-one" {...props}></Icon>
