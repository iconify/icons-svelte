<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hegyw304a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hegyw304a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:ai-generate-voice-robot-2-solid" {...props}></Icon>
