<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okeprsxkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okeprsxkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:audio-waveform" {...props}></Icon>
