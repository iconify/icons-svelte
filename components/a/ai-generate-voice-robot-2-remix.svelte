<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrwvep5rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qrwvep5rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:ai-generate-voice-robot-2-remix" {...props}></Icon>
