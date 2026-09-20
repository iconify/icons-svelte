<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t99-0xbvy.css';
import '../../css/o/ogs-x9j_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t99-0xbvy"/><path clip-rule="evenodd" class="ogs-x9j_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:mic-duotone" {...props}></Icon>
