<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh6eqlk_e.css';
import '../../css/d/dqmh4gbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mh6eqlk_e"/><path class="dqmh4gbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:camera-tripod-bold" {...props}></Icon>
