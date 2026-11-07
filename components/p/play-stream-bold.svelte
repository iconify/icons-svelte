<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayzb5ccgl.css';
import '../../css/s/sdtufnbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ayzb5ccgl"/><path class="sdtufnbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:play-stream-bold" {...props}></Icon>
