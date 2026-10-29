<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bak1p_6df.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bak1p_6df"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-up-solid" {...props}></Icon>
