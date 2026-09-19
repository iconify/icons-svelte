<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6na3qejl.css';
import '../../css/z/zneq0wbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q6na3qejl"/><path class="zneq0wbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:location-info-filled" {...props}></Icon>
