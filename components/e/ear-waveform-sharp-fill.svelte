<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf2bj-wdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zf2bj-wdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:ear-waveform-sharp-fill" {...props}></Icon>
