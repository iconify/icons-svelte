<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_uuu056f.css';
import '../../css/q/qdis4za-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_uuu056f"/><path class="qdis4za-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:blogger-alt" {...props}></Icon>
