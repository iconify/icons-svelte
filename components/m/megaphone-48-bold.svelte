<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjut8esur.css';
import '../../css/u/ujxou552b.css';
import '../../css/h/h02k7abwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tjut8esur"/><path class="ujxou552b"/><path class="h02k7abwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:megaphone-48-bold" {...props}></Icon>
