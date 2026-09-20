<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt38cn2hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt38cn2hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:pencil-sketch" {...props}></Icon>
