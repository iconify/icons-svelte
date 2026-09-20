<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4plhrqgv.css';
import '../../css/q/qsn33xeca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w4plhrqgv"/><path class="qsn33xeca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-astro-open" {...props}></Icon>
