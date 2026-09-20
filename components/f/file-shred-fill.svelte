<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk9fspbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk9fspbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-shred-fill" {...props}></Icon>
