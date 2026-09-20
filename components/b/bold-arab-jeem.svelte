<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u21y36n3m.css';
import '../../css/q/qtj8v8b9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u21y36n3m"/><circle class="qtj8v8b9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:bold-arab-jeem" {...props}></Icon>
