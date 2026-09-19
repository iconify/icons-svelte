<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyzi_3zlw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyzi_3zlw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ollama" {...props}></Icon>
