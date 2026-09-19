<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd-_2wbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vd-_2wbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ha-voice-pe" {...props}></Icon>
