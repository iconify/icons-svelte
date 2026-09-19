<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kique1x5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kique1x5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:codesandbox" {...props}></Icon>
