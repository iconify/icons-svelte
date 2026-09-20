<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj_h7sufq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mj_h7sufq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-forbid-fill" {...props}></Icon>
