<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jywu-rbdx.css';
import '../../css/h/hppnn5bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jywu-rbdx"/><path class="hppnn5bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:obs-bygg" {...props}></Icon>
