<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haf1n5bdl.css';
import '../../css/b/bn2yvfnzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="haf1n5bdl"/><path class="bn2yvfnzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-benchmark-open" {...props}></Icon>
