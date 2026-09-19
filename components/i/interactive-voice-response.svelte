<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvp85bpbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mvp85bpbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:interactive-voice-response" {...props}></Icon>
