<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drz0z9bei.css';
import '../../css/j/jcbxfnaqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="drz0z9bei"/><path class="jcbxfnaqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ear-48" {...props}></Icon>
