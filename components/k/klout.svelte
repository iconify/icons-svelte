<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj2dwebww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uj2dwebww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:klout" {...props}></Icon>
