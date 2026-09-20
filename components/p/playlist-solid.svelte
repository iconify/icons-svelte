<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5vpj0gqk.css';
import '../../css/m/m87stabfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5vpj0gqk"/><path class="m87stabfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:playlist-solid" {...props}></Icon>
