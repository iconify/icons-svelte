<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah05wvbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ah05wvbic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:atres-player" {...props}></Icon>
