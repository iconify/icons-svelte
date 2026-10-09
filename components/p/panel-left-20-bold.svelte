<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkpulpb9y.css';
import '../../css/a/acc7t232x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jkpulpb9y"/><path class="acc7t232x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:panel-left-20-bold" {...props}></Icon>
