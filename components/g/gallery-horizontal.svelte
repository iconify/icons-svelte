<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyzaa1b7x.css';
import '../../css/l/labyc9bkw.css';
import '../../css/k/kmcx5kbxj.css';
import '../../css/g/g6e0-4tfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyzaa1b7x wm-a"/><path class="labyc9bkw wm-k"/><path class="kmcx5kbxj wm-k"/><path class="g6e0-4tfd wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:gallery-horizontal" {...props}></Icon>
