<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahlge8buh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ahlge8buh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:creative-commons" {...props}></Icon>
