<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1ndnv3mj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1ndnv3mj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:help-circle" {...props}></Icon>
