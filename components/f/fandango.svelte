<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfivm5bwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lfivm5bwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:fandango" {...props}></Icon>
