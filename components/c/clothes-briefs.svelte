<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auw0m7xud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="auw0m7xud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:clothes-briefs" {...props}></Icon>
