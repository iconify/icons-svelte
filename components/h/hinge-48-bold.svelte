<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6yz84b5g.css';
import '../../css/e/e2u938bif.css';
import '../../css/f/f1mld5bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j6yz84b5g"/><path class="e2u938bif"/><path class="f1mld5bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hinge-48-bold" {...props}></Icon>
