<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv0mj9bsl.css';
import '../../css/h/hmo75wbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="cv0mj9bsl"/><path class="hmo75wbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:camera-sharp" {...props}></Icon>
