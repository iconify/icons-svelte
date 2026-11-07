<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si6y8idcw.css';
import '../../css/w/w8iuawbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="si6y8idcw"/><path clip-rule="evenodd" class="w8iuawbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:microphone-bold" {...props}></Icon>
