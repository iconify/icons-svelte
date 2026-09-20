<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb28jib9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jb28jib9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:bluetooth" {...props}></Icon>
