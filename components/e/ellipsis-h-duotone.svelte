<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx93t8bdb.css';
import '../../css/b/bj2qr51xp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mx93t8bdb"/><path clip-rule="evenodd" class="bj2qr51xp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:ellipsis-h-duotone" {...props}></Icon>
