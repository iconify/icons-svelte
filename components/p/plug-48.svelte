<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haxjj3y8l.css';
import '../../css/c/ca098sbgi.css';
import '../../css/p/pbj3dmu5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="haxjj3y8l"/><path class="ca098sbgi"/><path class="pbj3dmu5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plug-48" {...props}></Icon>
