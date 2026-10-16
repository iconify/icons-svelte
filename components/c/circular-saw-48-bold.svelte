<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bydf-9bza.css';
import '../../css/f/fe7lf8b9s.css';
import '../../css/e/e54qfbcyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bydf-9bza"/><path class="fe7lf8b9s"/><path class="e54qfbcyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:circular-saw-48-bold" {...props}></Icon>
