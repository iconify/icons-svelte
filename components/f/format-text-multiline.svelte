<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdt0fxxjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="mdt0fxxjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:format-text-multiline" {...props}></Icon>
