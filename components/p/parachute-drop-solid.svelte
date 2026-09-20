<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sinzbcb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sinzbcb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:parachute-drop-solid" {...props}></Icon>
