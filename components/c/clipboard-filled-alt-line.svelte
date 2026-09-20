<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvas_sv5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvas_sv5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:clipboard-filled-alt-line" {...props}></Icon>
