<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va3vigmkv.css';
import '../../css/q/qsn33xeca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="va3vigmkv"/><path class="qsn33xeca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-astro" {...props}></Icon>
