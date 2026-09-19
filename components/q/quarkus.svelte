<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t41a-9_dl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t41a-9_dl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:quarkus" {...props}></Icon>
