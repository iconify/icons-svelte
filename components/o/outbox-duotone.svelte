<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df7pajbkm.css';
import '../../css/n/n6jizwbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="df7pajbkm"/><path class="n6jizwbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:outbox-duotone" {...props}></Icon>
