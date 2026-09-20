<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld4ywrboa.css';
import '../../css/q/qsvb7nb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ld4ywrboa"/><path class="qsvb7nb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mosque-filled" {...props}></Icon>
