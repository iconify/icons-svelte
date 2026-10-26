<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1bjk9b9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h1bjk9b9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:library" {...props}></Icon>
