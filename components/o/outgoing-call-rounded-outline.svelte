<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy2l7ab8f.css';
import '../../css/s/s6xf6abum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zy2l7ab8f"/><path class="s6xf6abum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:outgoing-call-rounded-outline" {...props}></Icon>
