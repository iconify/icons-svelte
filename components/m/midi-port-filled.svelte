<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldfradshm.css';
import '../../css/i/itrl4jbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ldfradshm"/><path class="itrl4jbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:midi-port-filled" {...props}></Icon>
