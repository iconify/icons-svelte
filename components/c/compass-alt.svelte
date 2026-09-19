<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzt08gbvp.css';
import '../../css/i/i2pz7cbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzt08gbvp"/><path class="i2pz7cbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:compass-alt" {...props}></Icon>
