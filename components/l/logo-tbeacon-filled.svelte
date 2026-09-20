<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scsbkobgd.css';
import '../../css/r/ro_92tjwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scsbkobgd"/><path class="ro_92tjwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-tbeacon-filled" {...props}></Icon>
