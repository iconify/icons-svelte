<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8nb3i--r.css';
import '../../css/m/m3w96hble.css';
import '../../css/y/yvkzvdbqw.css';
import '../../css/s/sfuacrboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g8nb3i--r"/><path class="m3w96hble"/><path class="yvkzvdbqw"/><path class="sfuacrboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:photography-focus-flower" {...props}></Icon>
