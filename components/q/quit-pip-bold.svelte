<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz0u67btj.css';
import '../../css/x/x3oufibth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tz0u67btj"/><path class="x3oufibth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:quit-pip-bold" {...props}></Icon>
