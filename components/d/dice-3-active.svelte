<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5omho7-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g5omho7-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:dice-3-active" {...props}></Icon>
