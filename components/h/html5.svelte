<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahw-91_je.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="ahw-91_je"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:html5" {...props}></Icon>
