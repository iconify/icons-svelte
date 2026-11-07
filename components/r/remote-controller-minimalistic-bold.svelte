<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdbfs0bsu.css';
import '../../css/r/riimeibow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdbfs0bsu"/><path clip-rule="evenodd" class="riimeibow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:remote-controller-minimalistic-bold" {...props}></Icon>
