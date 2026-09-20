<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apd_cdc3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="apd_cdc3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:format-italic" {...props}></Icon>
