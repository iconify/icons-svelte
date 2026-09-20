<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swoo4rbsl.css';
import '../../css/u/ukyr80b4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swoo4rbsl"/><path class="ukyr80b4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:cassette-tape-solid" {...props}></Icon>
