<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra69dbbfc.css';
import '../../css/u/u0vmqablo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ra69dbbfc"/><path class="u0vmqablo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:download-alt-solid" {...props}></Icon>
