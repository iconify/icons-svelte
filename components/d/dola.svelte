<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf70dbbds.css';
import '../../css/r/rwk1vccqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sf70dbbds"/><path class="rwk1vccqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dola" {...props}></Icon>
