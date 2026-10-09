<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v16uh-byn.css';
import '../../css/s/sahyts8de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v16uh-byn"/><path class="sahyts8de"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hiking-48" {...props}></Icon>
