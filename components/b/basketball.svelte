<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-vd9z53y.css';
import '../../css/b/bwdisqe6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-vd9z53y wm-a"/><path class="bwdisqe6r wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:basketball" {...props}></Icon>
