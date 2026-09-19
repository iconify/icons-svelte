<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tas75n0ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tas75n0ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:azure-pipelines" {...props}></Icon>
