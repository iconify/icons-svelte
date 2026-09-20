<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-i3y8b7c.css';
import '../../css/e/ecd9gs9sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h-i3y8b7c"/><path class="ecd9gs9sn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:last-updates-duotone" {...props}></Icon>
