<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxc9xxbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxc9xxbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:clock2-filled" {...props}></Icon>
