<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyw18zbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gyw18zbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:http" {...props}></Icon>
